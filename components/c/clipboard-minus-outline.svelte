<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3cnu0b3i.css';
import '../../css/e/e3rn21oia.css';
import '../../css/e/e67e0wblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3cnu0b3i"/><path class="e3rn21oia"/><path class="e67e0wblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-minus-outline" {...props}></Icon>
