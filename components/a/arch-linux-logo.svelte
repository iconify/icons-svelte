<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaz-7ebrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaz-7ebrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:arch-linux-logo" {...props}></Icon>
