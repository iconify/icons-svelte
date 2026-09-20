<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o20ksdzpf.css';
import '../../css/h/hbx3odb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o20ksdzpf"/><path class="hbx3odb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cybersecurity" {...props}></Icon>
