<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqn4ghivr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bqn4ghivr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:input-box" {...props}></Icon>
