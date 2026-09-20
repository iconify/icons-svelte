<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujhqrdbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujhqrdbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:insights-line" {...props}></Icon>
