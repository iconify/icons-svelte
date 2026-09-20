<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez1yabb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ez1yabb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:factory-plant-remix" {...props}></Icon>
