<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jprajcb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jprajcb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mars" {...props}></Icon>
