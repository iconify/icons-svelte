<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl0w_em6f.css';
import '../../css/q/qeuinobue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="jl0w_em6f"/><path class="qeuinobue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbdo" {...props}></Icon>
