<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klpb0dbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="klpb0dbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:graduation-cap-filled" {...props}></Icon>
