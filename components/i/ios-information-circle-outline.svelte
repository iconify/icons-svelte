<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdowcxbbg.css';
import '../../css/l/lalksfbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gdowcxbbg"/><path class="lalksfbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-information-circle-outline" {...props}></Icon>
