<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftl1fs6jj.css';
import '../../css/f/fv1vecnlt.css';
import '../../css/f/flan3pe2x.css';
import '../../css/a/ak5u0_npi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ftl1fs6jj"/><path class="fv1vecnlt"/><path clip-rule="evenodd" class="flan3pe2x"/><path clip-rule="evenodd" class="ak5u0_npi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iammeter-dark" {...props}></Icon>
