<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9ha_eclp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9ha_eclp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lamp-filled" {...props}></Icon>
