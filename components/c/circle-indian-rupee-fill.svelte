<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8whwu36b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8whwu36b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-indian-rupee-fill" {...props}></Icon>
