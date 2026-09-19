<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbe-ueb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nbe-ueb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:female-reproductive-system-outline" {...props}></Icon>
