<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta9oaqh9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta9oaqh9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:monitor" {...props}></Icon>
