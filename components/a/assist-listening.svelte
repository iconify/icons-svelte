<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixn_89u5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixn_89u5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:assist-listening" {...props}></Icon>
