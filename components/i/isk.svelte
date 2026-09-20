<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn8q6fsbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn8q6fsbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:isk" {...props}></Icon>
