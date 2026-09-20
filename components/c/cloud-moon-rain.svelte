<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkydw766g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkydw766g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-moon-rain" {...props}></Icon>
