<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7b6jujxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7b6jujxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:laugh-fill" {...props}></Icon>
