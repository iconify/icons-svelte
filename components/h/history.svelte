<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t55uzkb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t55uzkb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:history" {...props}></Icon>
