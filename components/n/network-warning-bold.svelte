<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj7lf7-lu.css';
import '../../css/d/dt6i3k8yq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj7lf7-lu"/><path class="dt6i3k8yq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:network-warning-bold" {...props}></Icon>
