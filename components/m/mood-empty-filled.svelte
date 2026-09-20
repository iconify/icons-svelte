<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt30kgbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt30kgbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-empty-filled" {...props}></Icon>
