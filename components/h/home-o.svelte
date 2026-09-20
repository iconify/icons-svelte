<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivqu7ub_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ivqu7ub_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:home-o" {...props}></Icon>
