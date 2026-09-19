<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e73n2wbci.css';
import '../../css/t/ts2ygdnsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e73n2wbci"/><path class="ts2ygdnsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:return-up-forward-sharp" {...props}></Icon>
