<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slrdw5b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="slrdw5b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:c-outline" {...props}></Icon>
