<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng-l8i51q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ng-l8i51q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:flag" {...props}></Icon>
