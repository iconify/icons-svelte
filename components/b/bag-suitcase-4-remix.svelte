<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mex-ngb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mex-ngb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bag-suitcase-4-remix" {...props}></Icon>
