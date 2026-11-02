<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m236ioque.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m236ioque"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:escalator-up-line" {...props}></Icon>
