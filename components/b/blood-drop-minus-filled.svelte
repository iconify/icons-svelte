<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrr0wcb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrr0wcb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:blood-drop-minus-filled" {...props}></Icon>
