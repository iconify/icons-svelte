<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_487xz5h.css';
import '../../css/a/a-n77rjap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_487xz5h"/><path class="a-n77rjap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:countly" {...props}></Icon>
