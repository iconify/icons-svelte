<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp60v3b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jp60v3b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:moustache-solid" {...props}></Icon>
