<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-_vrw8jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-_vrw8jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:quad9" {...props}></Icon>
