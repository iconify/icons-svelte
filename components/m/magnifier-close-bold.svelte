<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6tuhvb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i6tuhvb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-close-bold" {...props}></Icon>
