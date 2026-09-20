<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9_-_eiow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p9_-_eiow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:arch-linux-logo-block" {...props}></Icon>
