<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-8j-ebpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-8j-ebpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:artifact-hub" {...props}></Icon>
