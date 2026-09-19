<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su6b2s4_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="su6b2s4_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-plus-fill" {...props}></Icon>
