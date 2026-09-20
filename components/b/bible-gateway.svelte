<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvfeg8nzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jvfeg8nzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bible-gateway" {...props}></Icon>
