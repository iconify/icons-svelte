<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2j9mlb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a2j9mlb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:arnx" {...props}></Icon>
