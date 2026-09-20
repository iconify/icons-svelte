<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrsopzbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qrsopzbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:incognito-mode-solid" {...props}></Icon>
