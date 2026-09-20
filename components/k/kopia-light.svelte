<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j73f_zbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j73f_zbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kopia-light" {...props}></Icon>
