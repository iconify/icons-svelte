<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_gx5lmul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_gx5lmul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rectangle-vertical-filled" {...props}></Icon>
