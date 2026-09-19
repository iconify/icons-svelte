<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o18pi7bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o18pi7bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:check-compact" {...props}></Icon>
