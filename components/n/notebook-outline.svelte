<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi3uknbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fi3uknbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notebook-outline" {...props}></Icon>
