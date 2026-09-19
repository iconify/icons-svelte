<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di7y9flmv.css';
import '../../css/t/tsepx-fqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="di7y9flmv"/><path class="tsepx-fqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:phrase-sentiment" {...props}></Icon>
