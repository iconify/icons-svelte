<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe_gizbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe_gizbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-up-down" {...props}></Icon>
