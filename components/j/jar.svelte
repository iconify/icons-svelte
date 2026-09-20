<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/pv84n0bii.css';
import '../../css/w/w8bgqeoji.css';
import '../../css/a/av4wpcl1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pv84n0bii"/><rect class="w8bgqeoji"/><path class="av4wpcl1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:jar" {...props}></Icon>
