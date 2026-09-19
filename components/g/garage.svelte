<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sab-3jbuj.css';
import '../../css/u/ugqzsebbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sab-3jbuj"/><path class="ugqzsebbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:garage" {...props}></Icon>
