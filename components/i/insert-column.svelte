<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeu2khb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qeu2khb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:insert-column" {...props}></Icon>
