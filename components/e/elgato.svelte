<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezq9uabrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezq9uabrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:elgato" {...props}></Icon>
