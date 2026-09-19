<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmt3q2buw.css';
import '../../css/q/qstrk3-9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zmt3q2buw"/><path class="qstrk3-9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:direction-rtl-fill-12" {...props}></Icon>
