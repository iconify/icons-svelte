<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulyepfb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulyepfb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gunicorn" {...props}></Icon>
