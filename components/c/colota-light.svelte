<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2e05bcja.css';
import '../../css/v/vojou6b4q.css';
import '../../css/f/f4pvf8bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d2e05bcja"/><path class="vojou6b4q"/><path class="f4pvf8bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:colota-light" {...props}></Icon>
