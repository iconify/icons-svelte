<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut64ajb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ut64ajb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-archive-outline" {...props}></Icon>
