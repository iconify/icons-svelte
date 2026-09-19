<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nomplj6bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nomplj6bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:clinical-a-outline" {...props}></Icon>
