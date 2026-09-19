<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_jz6jb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y_jz6jb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:leg-outline" {...props}></Icon>
