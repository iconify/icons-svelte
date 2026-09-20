<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy3jeobtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy3jeobtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:reply-duotone" {...props}></Icon>
