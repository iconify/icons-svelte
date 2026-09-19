<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd8zlbb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="qd8zlbb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:person-door-man" {...props}></Icon>
