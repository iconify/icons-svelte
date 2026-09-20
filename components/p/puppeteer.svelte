<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jspq5g4xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jspq5g4xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:puppeteer" {...props}></Icon>
