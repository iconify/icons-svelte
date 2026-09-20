<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjh0rhbxf.css';
import '../../css/w/w-b8g4otv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjh0rhbxf"/><path class="w-b8g4otv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:rain-umbrella-sun-bold" {...props}></Icon>
