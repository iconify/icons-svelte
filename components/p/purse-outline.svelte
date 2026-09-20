<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muz_lmbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="muz_lmbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:purse-outline" {...props}></Icon>
