<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caylp1yww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="caylp1yww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:health-worker" {...props}></Icon>
