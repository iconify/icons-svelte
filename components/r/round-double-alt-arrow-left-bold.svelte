<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0ahrne_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v0ahrne_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-double-alt-arrow-left-bold" {...props}></Icon>
