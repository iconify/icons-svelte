<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp55kxb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pp55kxb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:database-import" {...props}></Icon>
