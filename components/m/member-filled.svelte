<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6kz7fbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6kz7fbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:member-filled" {...props}></Icon>
