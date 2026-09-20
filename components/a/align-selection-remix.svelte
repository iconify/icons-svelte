<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj_9ii32x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mj_9ii32x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:align-selection-remix" {...props}></Icon>
