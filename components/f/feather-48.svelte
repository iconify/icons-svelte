<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zim1xe5fl.css';
import '../../css/i/is-_b_bvj.css';
import '../../css/q/qtbfkyb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zim1xe5fl"/><path class="is-_b_bvj"/><path class="qtbfkyb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:feather-48" {...props}></Icon>
