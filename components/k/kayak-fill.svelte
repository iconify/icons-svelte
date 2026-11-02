<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnrhg7ivd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnrhg7ivd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:kayak-fill" {...props}></Icon>
