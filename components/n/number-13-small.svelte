<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcs4akjag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcs4akjag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-13-small" {...props}></Icon>
