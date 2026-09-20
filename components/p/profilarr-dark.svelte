<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk1ci18po.css';
import '../../css/j/jwjgdy4tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mk1ci18po"/><path class="jwjgdy4tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:profilarr-dark" {...props}></Icon>
