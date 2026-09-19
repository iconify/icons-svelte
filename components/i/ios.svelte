<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnbd80b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnbd80b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ios" {...props}></Icon>
