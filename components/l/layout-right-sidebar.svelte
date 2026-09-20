<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-c2luh3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b-c2luh3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:layout-right-sidebar" {...props}></Icon>
