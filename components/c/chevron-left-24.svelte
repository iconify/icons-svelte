<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opby1ibzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opby1ibzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-left-24" {...props}></Icon>
