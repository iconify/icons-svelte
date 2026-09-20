<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no5pizbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="no5pizbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:frame-outline" {...props}></Icon>
