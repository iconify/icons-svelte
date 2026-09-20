<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjbeumbky.css';
import '../../css/c/ckze4557m.css';
import '../../css/o/o4qlo11nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yjbeumbky"/><path class="ckze4557m"/><path class="o4qlo11nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:leafwiki-dark" {...props}></Icon>
