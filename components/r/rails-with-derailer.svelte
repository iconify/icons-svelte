<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn7rt1cnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yn7rt1cnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:rails-with-derailer" {...props}></Icon>
