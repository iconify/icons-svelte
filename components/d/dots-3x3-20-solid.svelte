<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8pqa-bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q8pqa-bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-3x3-20-solid" {...props}></Icon>
