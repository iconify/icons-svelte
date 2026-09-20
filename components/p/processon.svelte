<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq4h2u3rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq4h2u3rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:processon" {...props}></Icon>
