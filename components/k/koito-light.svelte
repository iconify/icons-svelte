<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd0jd6bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xd0jd6bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:koito-light" {...props}></Icon>
