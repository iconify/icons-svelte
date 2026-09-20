<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4fu23kqa.css';
import '../../css/p/p--gbnsrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v4fu23kqa"/><path class="p--gbnsrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:beauty-mirror-2" {...props}></Icon>
