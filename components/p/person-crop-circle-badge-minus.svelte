<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gavx18bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gavx18bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-crop-circle-badge-minus" {...props}></Icon>
