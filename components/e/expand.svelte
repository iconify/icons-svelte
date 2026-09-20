<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm-q11b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lm-q11b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:expand" {...props}></Icon>
