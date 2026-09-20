<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kan81_beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kan81_beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:keyboard-sharp-fill" {...props}></Icon>
