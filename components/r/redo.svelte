<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyl6tnayy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyl6tnayy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:redo" {...props}></Icon>
