<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aafiimbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aafiimbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-15-seconds-forward-outline" {...props}></Icon>
