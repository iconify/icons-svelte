<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2s-7hbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2s-7hbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:gender-female" {...props}></Icon>
