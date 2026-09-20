<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq_4ykvlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pq_4ykvlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ferris-wheel-outline" {...props}></Icon>
