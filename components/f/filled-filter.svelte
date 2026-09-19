<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfmav5c8a.css';
import '../../css/k/k1fidk1yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jfmav5c8a"/><path class="k1fidk1yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:filled-filter" {...props}></Icon>
