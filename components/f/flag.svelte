<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4w_g2sig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y4w_g2sig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flag" {...props}></Icon>
