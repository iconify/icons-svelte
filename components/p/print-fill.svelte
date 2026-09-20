<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld1e0bb3t.css';
import '../../css/f/frzki349x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld1e0bb3t"/><path clip-rule="evenodd" class="frzki349x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:print-fill" {...props}></Icon>
