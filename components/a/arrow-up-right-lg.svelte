<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv84cpbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv84cpbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-up-right-lg" {...props}></Icon>
