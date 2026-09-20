<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gagg8eboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gagg8eboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:havells" {...props}></Icon>
