<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqa_u_4cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqa_u_4cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-broken" {...props}></Icon>
