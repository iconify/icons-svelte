<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2hcgcc2r.css';
import '../../css/m/mwvb097_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2hcgcc2r"/><path class="mwvb097_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:people-group" {...props}></Icon>
