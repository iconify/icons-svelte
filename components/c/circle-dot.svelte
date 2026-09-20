<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qww11omoa.css';
import '../../css/m/mhvhrv90s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qww11omoa"/><path class="mhvhrv90s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:circle-dot" {...props}></Icon>
