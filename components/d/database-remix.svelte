<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnpy1nbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cnpy1nbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:database-remix" {...props}></Icon>
