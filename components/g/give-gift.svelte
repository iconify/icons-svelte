<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd876c3xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd876c3xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:give-gift" {...props}></Icon>
