<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aooy8_0ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aooy8_0ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:remove-minus" {...props}></Icon>
