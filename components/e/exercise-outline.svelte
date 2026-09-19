<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyp6cc8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cuyp6cc8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:exercise-outline" {...props}></Icon>
