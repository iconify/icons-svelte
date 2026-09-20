<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyndq2b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pyndq2b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:flashlight-remix" {...props}></Icon>
