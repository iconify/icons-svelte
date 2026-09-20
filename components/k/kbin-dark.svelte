<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qove3cb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qove3cb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kbin-dark" {...props}></Icon>
