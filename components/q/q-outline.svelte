<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t64z20bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t64z20bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:q-outline" {...props}></Icon>
