<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjn8idhbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pjn8idhbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:github-release-monitor-dark" {...props}></Icon>
