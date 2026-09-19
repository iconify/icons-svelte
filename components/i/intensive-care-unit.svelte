<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzmmucb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jzmmucb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:intensive-care-unit" {...props}></Icon>
