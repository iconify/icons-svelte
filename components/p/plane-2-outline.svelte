<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq3ncxbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gq3ncxbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plane-2-outline" {...props}></Icon>
