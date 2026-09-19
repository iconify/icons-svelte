<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q330gzbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q330gzbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-pwa-outline" {...props}></Icon>
