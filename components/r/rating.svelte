<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfvx-db7p.css';
import '../../css/e/ecev0ub1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="kfvx-db7p"/><path class="ecev0ub1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:rating" {...props}></Icon>
