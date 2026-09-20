<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1o7qhb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m1o7qhb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:disk" {...props}></Icon>
