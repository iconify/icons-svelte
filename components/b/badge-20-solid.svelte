<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq76k3b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fq76k3b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:badge-20-solid" {...props}></Icon>
