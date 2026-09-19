<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnndvsa8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnndvsa8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:duco-2" {...props}></Icon>
