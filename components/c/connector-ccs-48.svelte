<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ect0zrm_l.css';
import '../../css/e/eing7xb8o.css';
import '../../css/b/b9-4p0nzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ect0zrm_l"/><path class="eing7xb8o"/><path class="b9-4p0nzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-ccs-48" {...props}></Icon>
