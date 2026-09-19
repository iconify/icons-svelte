<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acz7xhb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acz7xhb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-on-square" {...props}></Icon>
