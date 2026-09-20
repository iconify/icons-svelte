<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se0czkb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se0czkb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:door-fill" {...props}></Icon>
