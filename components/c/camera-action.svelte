<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs6pe8bhf.css';
import '../../css/u/uhsg7-z6r.css';
import '../../css/v/vn8_ajdxo.css';
import '../../css/o/oclompb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hs6pe8bhf"/><path class="uhsg7-z6r"/><path class="vn8_ajdxo"/><circle class="oclompb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:camera-action" {...props}></Icon>
