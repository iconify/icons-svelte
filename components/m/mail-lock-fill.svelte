<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkw7-5bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkw7-5bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-lock-fill" {...props}></Icon>
