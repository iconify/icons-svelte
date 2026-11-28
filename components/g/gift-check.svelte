<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqwtl1sfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqwtl1sfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:gift-check" {...props}></Icon>
