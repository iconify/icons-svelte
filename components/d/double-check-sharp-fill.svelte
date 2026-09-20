<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxl6s7b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxl6s7b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:double-check-sharp-fill" {...props}></Icon>
