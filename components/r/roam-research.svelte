<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot0p-jbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot0p-jbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:roam-research" {...props}></Icon>
