<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twzjjvbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twzjjvbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:broadcast-fill" {...props}></Icon>
