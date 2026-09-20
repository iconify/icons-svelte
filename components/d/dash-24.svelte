<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plk7a033w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plk7a033w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:dash-24" {...props}></Icon>
