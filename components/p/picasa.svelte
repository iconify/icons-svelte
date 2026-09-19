<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3vhyqp0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="o3vhyqp0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:picasa" {...props}></Icon>
