<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu2dad7bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu2dad7bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-5-fill" {...props}></Icon>
