<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jie5rdb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jie5rdb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-down-stipple" {...props}></Icon>
