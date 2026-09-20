<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grg7xwilx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grg7xwilx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:profile-fill" {...props}></Icon>
