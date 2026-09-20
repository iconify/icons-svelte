<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sohy9t3it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sohy9t3it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:factory-plant-solid" {...props}></Icon>
