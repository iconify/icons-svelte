<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnhtf_fam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnhtf_fam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:directory-line" {...props}></Icon>
