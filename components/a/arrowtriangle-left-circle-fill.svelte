<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb-r98ulw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cb-r98ulw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-left-circle-fill" {...props}></Icon>
