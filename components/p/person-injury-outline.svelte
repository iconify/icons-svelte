<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvwx6gb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvwx6gb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:person-injury-outline" {...props}></Icon>
