<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb23s9btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb23s9btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:keypad-outline" {...props}></Icon>
