<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/g/gey20ubqc.css';
import '../../css/w/wa4wf2brm.css';
import '../../css/r/r4god8b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="gey20ubqc"/><path class="wa4wf2brm"/><path class="r4god8b6l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:briefcase-light" {...props}></Icon>
