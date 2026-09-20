<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1025bbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1025bbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:bitcoin" {...props}></Icon>
