<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf9dwxbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf9dwxbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:beer" {...props}></Icon>
