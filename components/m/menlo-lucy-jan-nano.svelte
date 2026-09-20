<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr9n_rb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr9n_rb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:menlo-lucy-jan-nano" {...props}></Icon>
