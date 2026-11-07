<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzj2_rlmw.css';
import '../../css/r/r641g4blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzj2_rlmw"/><path class="r641g4blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:corkscrew-bold" {...props}></Icon>
