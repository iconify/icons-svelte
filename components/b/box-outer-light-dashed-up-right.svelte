<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tctkn4c7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tctkn4c7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-dashed-up-right" {...props}></Icon>
