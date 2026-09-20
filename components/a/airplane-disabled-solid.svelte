<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr2nrvggc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jr2nrvggc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:airplane-disabled-solid" {...props}></Icon>
