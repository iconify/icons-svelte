<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qssessobw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="qssessobw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-taxi" {...props}></Icon>
