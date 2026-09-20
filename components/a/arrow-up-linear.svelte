<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufif6wbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufif6wbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-linear" {...props}></Icon>
