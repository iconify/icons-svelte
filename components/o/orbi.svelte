<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abx_eo5fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abx_eo5fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:orbi" {...props}></Icon>
