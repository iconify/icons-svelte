<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwu41bb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwu41bb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:help-square-solid" {...props}></Icon>
