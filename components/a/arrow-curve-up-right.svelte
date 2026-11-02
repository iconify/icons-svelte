<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7ny22t_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7ny22t_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-up-right" {...props}></Icon>
