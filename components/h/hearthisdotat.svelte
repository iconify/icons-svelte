<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aytkx2b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aytkx2b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hearthisdotat" {...props}></Icon>
