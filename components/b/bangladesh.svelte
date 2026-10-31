<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeezzsgew.css';
import '../../css/l/lxcqcfbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="zeezzsgew"/><path class="lxcqcfbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:bangladesh" {...props}></Icon>
