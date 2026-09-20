<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4uplm-4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4uplm-4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:gift" {...props}></Icon>
