<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmonebc-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmonebc-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:droplet" {...props}></Icon>
