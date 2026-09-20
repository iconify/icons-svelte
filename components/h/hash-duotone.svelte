<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdtvrs_7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdtvrs_7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:hash-duotone" {...props}></Icon>
