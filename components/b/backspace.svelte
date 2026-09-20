<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpv1xwoom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpv1xwoom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:backspace" {...props}></Icon>
