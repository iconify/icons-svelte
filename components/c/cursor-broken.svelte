<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wql0g2wcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wql0g2wcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cursor-broken" {...props}></Icon>
