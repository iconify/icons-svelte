<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjg8qor2a.css';
import '../../css/k/kyzz2cc9p.css';
import '../../css/l/l9lokr6ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xjg8qor2a"/><path class="kyzz2cc9p"/><path class="l9lokr6ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-wrench-48-bold" {...props}></Icon>
