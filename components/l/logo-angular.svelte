<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0ya0vb5b.css';
import '../../css/e/enivfjbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t0ya0vb5b"/><path class="enivfjbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-angular" {...props}></Icon>
