<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr80jrxoc.css';
import '../../css/c/c_321cctz.css';
import '../../css/e/eo8l1gwux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="lr80jrxoc"/><path class="c_321cctz"/><path class="eo8l1gwux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:pacific-community" {...props}></Icon>
