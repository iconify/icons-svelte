<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl91i5v9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bl91i5v9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:case-round-minimalistic-bold" {...props}></Icon>
