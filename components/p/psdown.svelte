<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-cdc3b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":895,"height":1024};
const content = `<path class="o-cdc3b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:psdown" {...props}></Icon>
