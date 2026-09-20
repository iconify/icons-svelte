<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/ty3hqsxbs.css';
import '../../css/g/go75i7e2x.css';
import '../../css/y/y2zl39b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ty3hqsxbs"/><path class="go75i7e2x"/><path class="y2zl39b4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:loader-bold-duotone" {...props}></Icon>
