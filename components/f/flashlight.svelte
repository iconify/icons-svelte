<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8ob1qfny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8ob1qfny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:flashlight" {...props}></Icon>
