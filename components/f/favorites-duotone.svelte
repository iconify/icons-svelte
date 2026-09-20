<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wit9n4b-r.css';
import '../../css/i/ig9_8-b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wit9n4b-r"/><path class="ig9_8-b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:favorites-duotone" {...props}></Icon>
