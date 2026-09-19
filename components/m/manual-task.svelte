<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds6outb7u.css';
import '../../css/r/rhman1omc.css';
import '../../css/a/agu9lxblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<g transform="translate(0 947.638)" class="ds6outb7u"><rect class="rhman1omc"/><path class="agu9lxblm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:manual-task" {...props}></Icon>
