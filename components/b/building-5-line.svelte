<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4-av5bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4-av5bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-5-line" {...props}></Icon>
