<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9hvhxbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9hvhxbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-wide-narrow-line" {...props}></Icon>
