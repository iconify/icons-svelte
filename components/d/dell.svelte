<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz-3k2cdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz-3k2cdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dell" {...props}></Icon>
