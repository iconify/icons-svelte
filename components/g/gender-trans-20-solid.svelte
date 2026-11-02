<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm26vc1og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="sm26vc1og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-trans-20-solid" {...props}></Icon>
