<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o942gqbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o942gqbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrows-angle-expand" {...props}></Icon>
