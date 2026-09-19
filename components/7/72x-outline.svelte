<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhsep8akp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jhsep8akp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:72x-outline" {...props}></Icon>
