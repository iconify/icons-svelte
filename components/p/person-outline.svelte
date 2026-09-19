<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj0nmlbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xj0nmlbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:person-outline" {...props}></Icon>
