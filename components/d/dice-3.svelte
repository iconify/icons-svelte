<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iee106p3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iee106p3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dice-3" {...props}></Icon>
