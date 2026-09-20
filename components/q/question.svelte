<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vskh41bae.css';
import '../../css/y/y_g1oe_0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vskh41bae"/><path class="y_g1oe_0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:question" {...props}></Icon>
