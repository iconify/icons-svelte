<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7giafb7e.css';
import '../../css/a/az0bq2bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="e7giafb7e"/><path class="az0bq2bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:ok" {...props}></Icon>
