<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl17tqb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl17tqb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:erase" {...props}></Icon>
