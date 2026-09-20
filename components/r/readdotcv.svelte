<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlw6atb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlw6atb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:readdotcv" {...props}></Icon>
