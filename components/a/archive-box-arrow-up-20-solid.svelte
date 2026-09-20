<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm83secra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vm83secra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:archive-box-arrow-up-20-solid" {...props}></Icon>
