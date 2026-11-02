<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epm_5nbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epm_5nbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:axe-fill" {...props}></Icon>
