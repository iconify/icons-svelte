<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrmu94bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrmu94bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-drop-up-fill" {...props}></Icon>
