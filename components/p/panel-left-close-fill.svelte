<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uarib6_cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uarib6_cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-left-close-fill" {...props}></Icon>
