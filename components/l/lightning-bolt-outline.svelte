<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x75wll2yq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x75wll2yq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:lightning-bolt-outline" {...props}></Icon>
