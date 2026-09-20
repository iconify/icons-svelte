<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in2o_h8de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="in2o_h8de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:align-right" {...props}></Icon>
