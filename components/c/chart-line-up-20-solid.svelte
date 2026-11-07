<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpj1jdbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dpj1jdbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chart-line-up-20-solid" {...props}></Icon>
