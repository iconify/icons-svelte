<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te-zfbc4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="te-zfbc4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pregnant-outline" {...props}></Icon>
