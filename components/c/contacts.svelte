<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/y/yqzgd_r2w.css';
import '../../css/n/n9pgd6bqy.css';
import '../../css/c/c8-_myblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 3)" class="jtowsomii"><circle class="yqzgd_r2w"/><path class="n9pgd6bqy"/><path class="c8-_myblp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:contacts" {...props}></Icon>
