<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp-8ehbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bp-8ehbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:no-photo-taking-zone" {...props}></Icon>
