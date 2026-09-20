<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mamb4q5gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mamb4q5gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:backspace-a" {...props}></Icon>
