<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-vu-m6pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f-vu-m6pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:private-captcha-light" {...props}></Icon>
