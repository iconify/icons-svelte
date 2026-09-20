<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3ig99beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3ig99beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-specialty-feet-bold" {...props}></Icon>
