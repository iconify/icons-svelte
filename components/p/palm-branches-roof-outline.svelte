<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9sgzxuyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f9sgzxuyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:palm-branches-roof-outline" {...props}></Icon>
