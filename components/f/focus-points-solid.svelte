<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytl2035my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ytl2035my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:focus-points-solid" {...props}></Icon>
