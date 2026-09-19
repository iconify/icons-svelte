<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk_9v_7sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fk_9v_7sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-suit" {...props}></Icon>
