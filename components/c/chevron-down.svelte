<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gipd11bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gipd11bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chevron-down" {...props}></Icon>
