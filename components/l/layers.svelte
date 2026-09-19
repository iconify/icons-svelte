<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-dmpsp-p.css';
import '../../css/e/eeukgofxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g-dmpsp-p"/><path class="eeukgofxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:layers" {...props}></Icon>
