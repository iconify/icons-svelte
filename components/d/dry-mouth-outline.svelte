<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg9fl3bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jg9fl3bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dry-mouth-outline" {...props}></Icon>
