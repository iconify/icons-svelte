<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myp4mhcjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myp4mhcjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anvil-line" {...props}></Icon>
