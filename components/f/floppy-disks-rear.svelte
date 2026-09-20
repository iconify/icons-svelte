<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/b70_v8m2q.css';
import '../../css/p/p1sjor0su.css';
import '../../css/w/wvbjc1o2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b70_v8m2q"/><circle class="p1sjor0su"/><path class="wvbjc1o2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:floppy-disks-rear" {...props}></Icon>
