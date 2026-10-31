<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5lckz1mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m5lckz1mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-3x2-20-solid" {...props}></Icon>
