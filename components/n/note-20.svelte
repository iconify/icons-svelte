<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o976p-bam.css';
import '../../css/s/scecasm2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o976p-bam"/><path class="scecasm2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:note-20" {...props}></Icon>
