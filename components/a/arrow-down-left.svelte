<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jesqx4bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jesqx4bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-down-left" {...props}></Icon>
