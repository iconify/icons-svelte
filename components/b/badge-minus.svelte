<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7w31l30f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7w31l30f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:badge-minus" {...props}></Icon>
