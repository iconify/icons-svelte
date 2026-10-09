<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrc_6036o.css';
import '../../css/a/a99fs7b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hrc_6036o"/><path class="a99fs7b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:highlighter-48-bold" {...props}></Icon>
