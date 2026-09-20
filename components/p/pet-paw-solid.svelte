<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb-db-d4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tb-db-d4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pet-paw-solid" {...props}></Icon>
