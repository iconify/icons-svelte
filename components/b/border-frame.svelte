<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecydzj17y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ecydzj17y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:border-frame" {...props}></Icon>
