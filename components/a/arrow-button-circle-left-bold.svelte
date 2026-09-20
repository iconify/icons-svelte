<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk-frvbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk-frvbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-button-circle-left-bold" {...props}></Icon>
