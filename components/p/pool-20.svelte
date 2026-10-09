<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfl-1pr-y.css';
import '../../css/b/b8fd5ibpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lfl-1pr-y"/><path class="b8fd5ibpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pool-20" {...props}></Icon>
