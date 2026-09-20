<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh4qz-4wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh4qz-4wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-secure-outline" {...props}></Icon>
