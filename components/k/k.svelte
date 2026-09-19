<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcw0tzvsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fcw0tzvsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:k" {...props}></Icon>
