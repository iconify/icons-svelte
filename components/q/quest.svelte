<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6kz59bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6kz59bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:quest" {...props}></Icon>
