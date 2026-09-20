<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvv31odee.css';
import '../../css/c/c8c70ibjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvv31odee"/><path class="c8c70ibjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:playwright" {...props}></Icon>
