<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-r6ewgyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e-r6ewgyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bowl-chop-stick-solid" {...props}></Icon>
