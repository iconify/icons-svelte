<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-37ybbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-37ybbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jio" {...props}></Icon>
