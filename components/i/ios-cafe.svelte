<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi8qeub9j.css';
import '../../css/g/gzw_lcbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bi8qeub9j"/><path class="gzw_lcbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cafe" {...props}></Icon>
