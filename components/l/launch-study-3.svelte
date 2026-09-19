<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4wx7em1k.css';
import '../../css/a/a5g7susyd.css';
import '../../css/o/oi5qvth7c.css';
import '../../css/i/iqd4-rvaq.css';
import '../../css/w/weo7tpp0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="p4wx7em1k"/><path class="a5g7susyd"/><path class="oi5qvth7c"/><path class="iqd4-rvaq"/><path class="weo7tpp0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:launch-study-3" {...props}></Icon>
