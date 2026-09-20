<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecxct7tly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecxct7tly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:claris" {...props}></Icon>
