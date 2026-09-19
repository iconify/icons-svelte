<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bem5i2brp.css';
import '../../css/c/cohp0c6uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bem5i2brp"/><path class="cohp0c6uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ice-cream-outline" {...props}></Icon>
