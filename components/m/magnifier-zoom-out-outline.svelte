<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqjpo8w2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hqjpo8w2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-zoom-out-outline" {...props}></Icon>
