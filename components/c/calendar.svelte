<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glf6v1jiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glf6v1jiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:calendar" {...props}></Icon>
