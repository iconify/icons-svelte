<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw76rpbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lw76rpbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:download-circle-solid" {...props}></Icon>
