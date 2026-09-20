<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4uu2zbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g4uu2zbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:flush" {...props}></Icon>
