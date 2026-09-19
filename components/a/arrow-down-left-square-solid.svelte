<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tttity4uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tttity4uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-down-left-square-solid" {...props}></Icon>
