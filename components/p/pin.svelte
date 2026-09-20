<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iddesy17d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iddesy17d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:pin" {...props}></Icon>
