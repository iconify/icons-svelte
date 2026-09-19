<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln2xiy3fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln2xiy3fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:anchor" {...props}></Icon>
