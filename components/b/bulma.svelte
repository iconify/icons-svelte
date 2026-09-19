<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_x_tgb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t_x_tgb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:bulma" {...props}></Icon>
