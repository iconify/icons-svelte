<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyuip7b1u.css';
import '../../css/d/d4yg8obpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hyuip7b1u"/><path class="d4yg8obpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-merge-agent-16" {...props}></Icon>
