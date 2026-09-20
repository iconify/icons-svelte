<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygdyhhsoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygdyhhsoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-solid" {...props}></Icon>
