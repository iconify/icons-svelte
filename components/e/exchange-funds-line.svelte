<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4fw1mb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4fw1mb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:exchange-funds-line" {...props}></Icon>
