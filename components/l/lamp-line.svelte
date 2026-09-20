<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5bck-xcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5bck-xcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:lamp-line" {...props}></Icon>
