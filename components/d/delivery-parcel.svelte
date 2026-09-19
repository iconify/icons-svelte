<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjv214_sf.css';
import '../../css/j/j87t2qbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wjv214_sf"/><path class="j87t2qbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:delivery-parcel" {...props}></Icon>
