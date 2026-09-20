<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqsr4ccir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="qqsr4ccir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-round-up-left" {...props}></Icon>
