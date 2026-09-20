<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2bylrb9j.css';
import '../../css/i/ijc0stb4c.css';
import '../../css/x/x3n8gwoar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s2bylrb9j"/><path class="ijc0stb4c"/><path class="x3n8gwoar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:diploma" {...props}></Icon>
