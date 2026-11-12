<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg_nm4bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg_nm4bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:link-exclamation" {...props}></Icon>
