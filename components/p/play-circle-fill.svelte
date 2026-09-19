<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op10nbbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="op10nbbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:play-circle-fill" {...props}></Icon>
