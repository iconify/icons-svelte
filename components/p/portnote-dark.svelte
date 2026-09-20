<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhp86_bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lhp86_bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portnote-dark" {...props}></Icon>
