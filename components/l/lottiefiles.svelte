<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnw54xggm.css';
import '../../css/v/vi0lh-h6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnw54xggm"/><path class="vi0lh-h6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:lottiefiles" {...props}></Icon>
