<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flj_s0bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="flj_s0bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:outpatient-department" {...props}></Icon>
