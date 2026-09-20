<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7f8ufmsj.css';
import '../../css/a/abjuxlr8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7f8ufmsj"/><path class="abjuxlr8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:geeftlist-light" {...props}></Icon>
