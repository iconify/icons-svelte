<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-e3w7bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t-e3w7bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cut-16" {...props}></Icon>
