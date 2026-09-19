<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_b0f49ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_b0f49ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:heptagon-fill" {...props}></Icon>
