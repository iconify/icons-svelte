<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa6kjeb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fa6kjeb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:boy-0105y" {...props}></Icon>
