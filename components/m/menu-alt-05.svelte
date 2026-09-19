<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdhez3b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdhez3b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:menu-alt-05" {...props}></Icon>
