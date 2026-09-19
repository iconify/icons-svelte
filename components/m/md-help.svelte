<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv4n9hbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qv4n9hbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-help" {...props}></Icon>
