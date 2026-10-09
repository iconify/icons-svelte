<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ersub-k.css';
import '../../css/b/bpoutcsqa.css';
import '../../css/v/v_i9e3d-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x4ersub-k"/><path class="bpoutcsqa"/><path class="v_i9e3d-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-pull-request-48" {...props}></Icon>
