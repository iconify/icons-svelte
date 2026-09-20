<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-4nj7z5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-4nj7z5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:megaphone-b-fill" {...props}></Icon>
