<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyz42abor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyz42abor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:moon" {...props}></Icon>
