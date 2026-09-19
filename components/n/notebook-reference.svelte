<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lswr9wrdr.css';
import '../../css/u/unos9unxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lswr9wrdr"/><path class="unos9unxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:notebook-reference" {...props}></Icon>
