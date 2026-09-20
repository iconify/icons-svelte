<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly-8_lh2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ly-8_lh2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:renren-logo-1-block" {...props}></Icon>
