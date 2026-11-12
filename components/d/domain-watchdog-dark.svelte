<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7d_9oypd.css';
import '../../css/l/luvx9bb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d7d_9oypd"/><path class="luvx9bb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-watchdog-dark" {...props}></Icon>
