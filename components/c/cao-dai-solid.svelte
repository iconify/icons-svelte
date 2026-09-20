<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgdli1bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pgdli1bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cao-dai-solid" {...props}></Icon>
