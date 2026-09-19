<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq5pa6f5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq5pa6f5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:9-now" {...props}></Icon>
