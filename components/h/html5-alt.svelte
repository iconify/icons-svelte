<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd6l-0h0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd6l-0h0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:html5-alt" {...props}></Icon>
