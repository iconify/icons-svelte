<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_5cy0b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u_5cy0b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-up-left" {...props}></Icon>
