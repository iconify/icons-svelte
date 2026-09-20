<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6g06eeaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g6g06eeaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:give-gift-solid" {...props}></Icon>
