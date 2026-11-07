<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu9c0-57j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gu9c0-57j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-15-seconds-back-outline" {...props}></Icon>
