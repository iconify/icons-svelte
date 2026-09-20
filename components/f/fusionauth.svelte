<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvz4neb7i.css';
import '../../css/o/o-xvump-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zvz4neb7i"/><path class="o-xvump-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fusionauth" {...props}></Icon>
