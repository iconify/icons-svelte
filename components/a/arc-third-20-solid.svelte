<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuwj-qb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cuwj-qb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arc-third-20-solid" {...props}></Icon>
