<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2nvl-0be.css';
import '../../css/l/lt7jyeb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2nvl-0be"/><path class="lt7jyeb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bacteria" {...props}></Icon>
