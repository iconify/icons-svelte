<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt_s0ux-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt_s0ux-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:layout-up-left-fill" {...props}></Icon>
