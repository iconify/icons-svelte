<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7xz85ucz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7xz85ucz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:riot-games-logo-solid" {...props}></Icon>
