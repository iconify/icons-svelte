<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgcf6i6wr.css';
import '../../css/y/yhd0eaczw.css';
import '../../css/w/wcc2lm_1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jgcf6i6wr"/><path class="yhd0eaczw"/><path class="wcc2lm_1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kamiyomu-dark" {...props}></Icon>
