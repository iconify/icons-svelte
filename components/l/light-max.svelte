<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au28p2riu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="au28p2riu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:light-max" {...props}></Icon>
