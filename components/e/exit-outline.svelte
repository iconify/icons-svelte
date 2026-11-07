<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njk-keb-f.css';
import '../../css/e/e3g82dqvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njk-keb-f"/><path clip-rule="evenodd" class="e3g82dqvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:exit-outline" {...props}></Icon>
