<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh2rg2bpe.css';
import '../../css/i/i9gf5actf.css';
import '../../css/e/e2wi94ygl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":140,"height":140};
const content = `<g transform="translate(10.508 10.205)" class="sh2rg2bpe"><circle class="i9gf5actf"/><path class="e2wi94ygl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:browserlist-light" {...props}></Icon>
