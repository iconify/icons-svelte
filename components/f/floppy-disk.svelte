<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/z6eswjbsp.css';
import '../../css/p/pvksh5_ap.css';
import '../../css/h/h6pfvubgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="z6eswjbsp"/><path class="pvksh5_ap"/><path class="h6pfvubgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:floppy-disk" {...props}></Icon>
