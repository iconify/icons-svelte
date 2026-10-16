<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpwlrrj0w.css';
import '../../css/b/bcnnsuiaf.css';
import '../../css/r/rjummxbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jpwlrrj0w"/><path class="bcnnsuiaf"/><path class="rjummxbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aluminium-20-bold" {...props}></Icon>
