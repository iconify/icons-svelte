<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9fjosb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9fjosb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:information-line" {...props}></Icon>
