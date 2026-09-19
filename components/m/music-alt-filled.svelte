<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhpwlgmyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhpwlgmyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:music-alt-filled" {...props}></Icon>
