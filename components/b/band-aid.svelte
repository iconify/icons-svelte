<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_66s4b0b.css';
import '../../css/d/dwwqc9d1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_66s4b0b"/><path class="dwwqc9d1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:band-aid" {...props}></Icon>
