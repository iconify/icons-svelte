<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsr5jwd6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rsr5jwd6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reply-bold" {...props}></Icon>
