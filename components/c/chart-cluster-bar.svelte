<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgpzimtyu.css';
import '../../css/b/bydz9ac_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hgpzimtyu"/><path class="bydz9ac_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-cluster-bar" {...props}></Icon>
