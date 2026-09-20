<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgj-ambzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bgj-ambzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-dashed-vertical-horizontal" {...props}></Icon>
