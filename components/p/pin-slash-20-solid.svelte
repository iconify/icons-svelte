<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1weedx-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="i1weedx-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pin-slash-20-solid" {...props}></Icon>
