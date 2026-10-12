<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wyg7z5kjh.css';
import '../../css/s/suqmocc3n.css';
import '../../css/d/dft9gzb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wyg7z5kjh"/><path class="suqmocc3n"/><path class="dft9gzb8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:dam-duotone" {...props}></Icon>
