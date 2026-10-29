<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9nmfjvdw.css';
import '../../css/c/cj8t6iwqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9nmfjvdw wm-k"/><path class="cj8t6iwqx wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:captions" {...props}></Icon>
