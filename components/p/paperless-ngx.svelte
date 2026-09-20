<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kws8bdc5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kws8bdc5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paperless-ngx" {...props}></Icon>
