<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3cl1ueir.css';
import '../../css/r/r04um0bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q3cl1ueir"/><path class="r04um0bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-cash" {...props}></Icon>
