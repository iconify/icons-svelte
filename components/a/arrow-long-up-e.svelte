<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5_l4yboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5_l4yboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-long-up-e" {...props}></Icon>
