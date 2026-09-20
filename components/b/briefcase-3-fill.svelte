<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfnbzcbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfnbzcbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:briefcase-3-fill" {...props}></Icon>
