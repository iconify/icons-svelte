<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoko0xp2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoko0xp2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:phpmyadmin" {...props}></Icon>
