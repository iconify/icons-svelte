<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-8i2fzae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-8i2fzae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:equal-solid" {...props}></Icon>
