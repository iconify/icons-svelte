<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwt8qti7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwt8qti7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:log-in" {...props}></Icon>
