<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upyut0o1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upyut0o1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-smile-plus-solid" {...props}></Icon>
