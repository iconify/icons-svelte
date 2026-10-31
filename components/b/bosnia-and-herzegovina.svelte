<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smj7c3byz.css';
import '../../css/i/ir3eif-7d.css';
import '../../css/v/vj4ug-bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="smj7c3byz"/><path class="ir3eif-7d"/><path class="vj4ug-bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:bosnia-and-herzegovina" {...props}></Icon>
