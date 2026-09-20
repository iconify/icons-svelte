<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t593mzfam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t593mzfam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:blockchain" {...props}></Icon>
