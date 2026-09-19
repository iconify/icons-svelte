<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2msgnz-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="q2msgnz-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:first-aid-briefcase" {...props}></Icon>
