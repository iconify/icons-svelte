<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpa7bhnqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpa7bhnqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:quicktime" {...props}></Icon>
