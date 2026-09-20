<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iap-kccsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iap-kccsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt-block" {...props}></Icon>
