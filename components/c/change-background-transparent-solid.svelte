<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6rrcnb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x6rrcnb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:change-background-transparent-solid" {...props}></Icon>
