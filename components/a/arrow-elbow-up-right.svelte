<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-42gfrws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-42gfrws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-elbow-up-right" {...props}></Icon>
