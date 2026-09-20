<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nczw8dlgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nczw8dlgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pause-fill" {...props}></Icon>
