<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9r-at6ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9r-at6ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pass-pending-line" {...props}></Icon>
