<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqu5shbcg.css';
import '../../css/x/x_zkkvfvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rqu5shbcg"/><path class="x_zkkvfvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:api-48-bold" {...props}></Icon>
