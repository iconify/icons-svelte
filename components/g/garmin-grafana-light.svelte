<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekjul2jux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ekjul2jux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:garmin-grafana-light" {...props}></Icon>
