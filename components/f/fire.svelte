<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7e5m7b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g7e5m7b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:fire" {...props}></Icon>
