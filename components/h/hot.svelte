<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnmskeb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":832,"height":1024};
const content = `<path class="wnmskeb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hot" {...props}></Icon>
