<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh1hgwpzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh1hgwpzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nginx-proxy-manager" {...props}></Icon>
