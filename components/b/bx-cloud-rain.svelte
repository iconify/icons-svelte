<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-yt7ibsl.css';
import '../../css/m/mfa8tygij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-yt7ibsl"/><path class="mfa8tygij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cloud-rain" {...props}></Icon>
