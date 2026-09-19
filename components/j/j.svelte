<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o213s7s2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o213s7s2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:j" {...props}></Icon>
