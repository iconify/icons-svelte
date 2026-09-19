<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvk93ab1t.css';
import '../../css/l/lalksfbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nvk93ab1t"/><path class="lalksfbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-checkmark-circle-outline" {...props}></Icon>
