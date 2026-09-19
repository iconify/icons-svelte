<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_fq0ob9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w_fq0ob9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-down-fill" {...props}></Icon>
