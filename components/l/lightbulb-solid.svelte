<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b44jyjbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b44jyjbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:lightbulb-solid" {...props}></Icon>
