<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfj52-bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfj52-bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lg-signiture" {...props}></Icon>
