<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nis8-pwmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="nis8-pwmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-file-folder-work-office-company-folder-supplies-file" {...props}></Icon>
