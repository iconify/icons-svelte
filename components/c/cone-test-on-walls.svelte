<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4llb9ccr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j4llb9ccr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cone-test-on-walls" {...props}></Icon>
