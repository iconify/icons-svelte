<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2de9_til.css';
import '../../css/e/ex7ib8bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2de9_til"/><path class="ex7ib8bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:course-down-bold-duotone" {...props}></Icon>
