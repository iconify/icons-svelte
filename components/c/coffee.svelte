<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvfri4b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvfri4b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:coffee" {...props}></Icon>
