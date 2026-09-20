<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaxq7qbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaxq7qbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-item-right-line" {...props}></Icon>
