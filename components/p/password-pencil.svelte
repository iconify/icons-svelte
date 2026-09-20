<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lks5r8mvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lks5r8mvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-pencil" {...props}></Icon>
