<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvlu12bfl.css';
import '../../css/k/kqfh3ccjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvlu12bfl"/><path class="kqfh3ccjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-reducer-48-bold" {...props}></Icon>
