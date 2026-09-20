<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu56lfw9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu56lfw9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:money-withdraw" {...props}></Icon>
