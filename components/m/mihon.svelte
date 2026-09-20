<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg6lk8tud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg6lk8tud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mihon" {...props}></Icon>
