<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms3yp7bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ms3yp7bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ball-solid" {...props}></Icon>
