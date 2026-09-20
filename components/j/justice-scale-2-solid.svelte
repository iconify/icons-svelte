<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe43akbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oe43akbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:justice-scale-2-solid" {...props}></Icon>
