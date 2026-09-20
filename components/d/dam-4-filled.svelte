<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umcxplilb.css';
import '../../css/r/r2vwgjbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umcxplilb"/><path class="r2vwgjbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dam-4-filled" {...props}></Icon>
