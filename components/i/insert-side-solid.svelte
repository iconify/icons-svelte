<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltoh_6b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ltoh_6b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:insert-side-solid" {...props}></Icon>
