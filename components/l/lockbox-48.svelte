<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba29q_65m.css';
import '../../css/f/f1favznrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ba29q_65m"/><path class="f1favznrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lockbox-48" {...props}></Icon>
