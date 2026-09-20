<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv7socc2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv7socc2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-right-stretch" {...props}></Icon>
