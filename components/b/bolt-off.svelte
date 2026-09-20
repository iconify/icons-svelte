<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf-tyyb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf-tyyb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bolt-off" {...props}></Icon>
