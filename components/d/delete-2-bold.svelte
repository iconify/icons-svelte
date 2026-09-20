<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecmj4ybyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecmj4ybyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:delete-2-bold" {...props}></Icon>
