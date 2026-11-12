<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p208krbfh.css';
import '../../css/q/qeuinobue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="p208krbfh"/><path class="qeuinobue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbdo" {...props}></Icon>
