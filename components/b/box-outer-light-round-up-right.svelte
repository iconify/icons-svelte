<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym6sbbbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ym6sbbbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-round-up-right" {...props}></Icon>
