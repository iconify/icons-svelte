<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp4u6spcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hp4u6spcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:compress-pdf-remix" {...props}></Icon>
