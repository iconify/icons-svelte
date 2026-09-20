<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8lx0vbrj.css';
import '../../css/v/vy0ldfbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8lx0vbrj"/><path class="vy0ldfbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:atlas" {...props}></Icon>
