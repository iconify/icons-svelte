<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlex6fahs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlex6fahs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-peanut" {...props}></Icon>
