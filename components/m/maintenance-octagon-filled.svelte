<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twiaix3mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twiaix3mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:maintenance-octagon-filled" {...props}></Icon>
