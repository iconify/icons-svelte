<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giho2bore.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giho2bore"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-i-small" {...props}></Icon>
