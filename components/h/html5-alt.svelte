<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llko29bid.css';
import '../../css/a/a9_rmzbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llko29bid"/><path class="a9_rmzbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:html5-alt" {...props}></Icon>
