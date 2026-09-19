<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/puuv1qb4b.css';
import '../../css/l/ley2zzm8d.css';
import '../../css/e/ezne57fdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="puuv1qb4b"/><path class="ley2zzm8d"/><path class="ezne57fdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:magnifying-glass-tilted-left" {...props}></Icon>
