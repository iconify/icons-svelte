<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru-z4wb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru-z4wb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:drupal" {...props}></Icon>
