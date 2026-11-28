<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn3q9eaqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn3q9eaqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-terminal-solid" {...props}></Icon>
