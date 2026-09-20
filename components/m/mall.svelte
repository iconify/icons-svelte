<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk99xzecf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lk99xzecf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mall" {...props}></Icon>
