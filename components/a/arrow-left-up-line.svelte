<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmry91get.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmry91get"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-up-line" {...props}></Icon>
