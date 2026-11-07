<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7krorbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x7krorbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-stars-outline" {...props}></Icon>
