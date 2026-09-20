<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c20s_fcwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c20s_fcwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-99-small" {...props}></Icon>
