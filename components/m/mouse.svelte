<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypditfboi.css';
import '../../css/j/j2j3gdcfi.css';
import '../../css/x/xxphl5biz.css';
import '../../css/y/yo5mywban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ypditfboi"/><path class="j2j3gdcfi"/><path class="xxphl5biz"/><path class="yo5mywban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mouse" {...props}></Icon>
