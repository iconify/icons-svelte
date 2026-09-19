<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujk35abet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ujk35abet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-vessel" {...props}></Icon>
