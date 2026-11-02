<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6wv1qb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6wv1qb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dutch-windmill-fill" {...props}></Icon>
