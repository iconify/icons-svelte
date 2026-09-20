<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efz6zcc6h.css';
import '../../css/i/i7sr6ubzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efz6zcc6h"/><path class="i7sr6ubzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:heading-3-solid" {...props}></Icon>
