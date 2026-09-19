<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/io1nfda-a.css';
import '../../css/i/ixwm5pqlj.css';
import '../../css/g/glrkmsbvq.css';
import '../../css/v/vtuln3fnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="io1nfda-a"/><path class="ixwm5pqlj"/><path class="glrkmsbvq"/><path class="vtuln3fnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-21" {...props}></Icon>
