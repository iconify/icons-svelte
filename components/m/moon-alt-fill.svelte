<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szo7gubys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szo7gubys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:moon-alt-fill" {...props}></Icon>
