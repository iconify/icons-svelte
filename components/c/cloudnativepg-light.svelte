<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq0rjgbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dq0rjgbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudnativepg-light" {...props}></Icon>
