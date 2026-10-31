<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn46_qbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kn46_qbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrows-crossing-20-solid" {...props}></Icon>
