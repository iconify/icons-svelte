<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxkx72bus.css';
import '../../css/b/byx4gtwse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="hxkx72bus"/><path class="byx4gtwse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:postgresql-wordmark" {...props}></Icon>
