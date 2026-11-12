<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1fuo1lvj.css';
import '../../css/s/sj_lllbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l1fuo1lvj"/><path class="sj_lllbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nicotine-plus-dark" {...props}></Icon>
