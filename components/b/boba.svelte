<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8b-p0atb.css';
import '../../css/r/rw8uhq80v.css';
import '../../css/f/f6u8m20fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8b-p0atb"/><path class="rw8uhq80v"/><path class="f6u8m20fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:boba" {...props}></Icon>
