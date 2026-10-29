<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhc-2qift.css';
import '../../css/h/h86hhf6yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhc-2qift"/><path class="h86hhf6yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:braces" {...props}></Icon>
