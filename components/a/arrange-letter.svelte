<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phb40rbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phb40rbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber-color:arrange-letter" {...props}></Icon>
