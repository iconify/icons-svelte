<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weu205tov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="weu205tov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ifixit" {...props}></Icon>
