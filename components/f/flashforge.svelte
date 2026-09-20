<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj8hq6oxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj8hq6oxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:flashforge" {...props}></Icon>
