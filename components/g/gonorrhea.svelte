<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rar_yq1pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rar_yq1pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gonorrhea" {...props}></Icon>
