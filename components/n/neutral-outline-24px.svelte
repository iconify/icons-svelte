<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj4ohyv-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj4ohyv-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:neutral-outline-24px" {...props}></Icon>
