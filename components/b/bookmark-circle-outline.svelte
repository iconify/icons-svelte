<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bit-6ubvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bit-6ubvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-circle-outline" {...props}></Icon>
