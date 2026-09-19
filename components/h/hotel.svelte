<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afvdaibxt.css';
import '../../css/w/wfvxprbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="afvdaibxt"/><path class="wfvxprbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hotel" {...props}></Icon>
