<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlh4lswzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hlh4lswzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:baby-female-0306m-outline" {...props}></Icon>
