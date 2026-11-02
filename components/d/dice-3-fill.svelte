<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whzzz92ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whzzz92ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dice-3-fill" {...props}></Icon>
