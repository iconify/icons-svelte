<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh_v2e1my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh_v2e1my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:device" {...props}></Icon>
