<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amvdw8b4x.css';
import '../../css/o/om9xhncdy.css';
import '../../css/h/h-ythmv4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amvdw8b4x"/><path class="om9xhncdy"/><path class="h-ythmv4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-europe" {...props}></Icon>
