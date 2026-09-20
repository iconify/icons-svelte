<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_iof5qug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_iof5qug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:framework7" {...props}></Icon>
