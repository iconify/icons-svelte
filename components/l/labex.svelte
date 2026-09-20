<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na5njzqfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na5njzqfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:labex" {...props}></Icon>
