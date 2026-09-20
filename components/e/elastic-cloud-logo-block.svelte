<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djpkk9btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="djpkk9btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:elastic-cloud-logo-block" {...props}></Icon>
