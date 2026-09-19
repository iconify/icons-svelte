<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg-ah_bfc.css';
import '../../css/e/e5ufuhb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qg-ah_bfc"/><path class="e5ufuhb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-gear-outline" {...props}></Icon>
