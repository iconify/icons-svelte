<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf_5uubqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf_5uubqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gnuprivacyguard" {...props}></Icon>
