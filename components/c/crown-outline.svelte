<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc97uuhut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc97uuhut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:crown-outline" {...props}></Icon>
