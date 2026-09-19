<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbhew13zs.css';
import '../../css/c/cbep2fbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jbhew13zs"/><path class="cbep2fbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:return-down-forward-sharp" {...props}></Icon>
