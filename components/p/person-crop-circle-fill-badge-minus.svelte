<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlyst4b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jlyst4b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-crop-circle-fill-badge-minus" {...props}></Icon>
