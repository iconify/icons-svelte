<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixkz_u45r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixkz_u45r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:equal-light" {...props}></Icon>
