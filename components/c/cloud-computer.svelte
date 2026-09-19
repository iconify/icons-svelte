<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjnz9-bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjnz9-bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:cloud-computer" {...props}></Icon>
