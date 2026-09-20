<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fngcuz2gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fngcuz2gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:oracle-logo" {...props}></Icon>
