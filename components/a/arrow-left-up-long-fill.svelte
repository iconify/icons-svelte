<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st1qoibzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st1qoibzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-up-long-fill" {...props}></Icon>
