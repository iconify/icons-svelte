<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2-_ejm0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2-_ejm0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:phone-minus" {...props}></Icon>
