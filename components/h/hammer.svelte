<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7uoh_pkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="t7uoh_pkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hammer" {...props}></Icon>
