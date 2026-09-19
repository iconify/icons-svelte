<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsue9y5zg.css';
import '../../css/s/sfzd15p1h.css';
import '../../css/z/zc__otrgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nsue9y5zg"/><path class="sfzd15p1h"/><path class="zc__otrgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:place" {...props}></Icon>
