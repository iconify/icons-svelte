<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8rlu56bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z8rlu56bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bill-1-remix" {...props}></Icon>
