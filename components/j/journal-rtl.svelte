<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukr-_lbgh.css';
import '../../css/y/yqzq-hios.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ukr-_lbgh"/><path class="yqzq-hios"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:journal-rtl" {...props}></Icon>
