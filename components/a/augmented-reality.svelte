<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7m4j-afs.css';
import '../../css/g/g4h-wyhlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7m4j-afs"/><path class="g4h-wyhlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:augmented-reality" {...props}></Icon>
