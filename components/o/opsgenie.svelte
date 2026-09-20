<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe2b1e9jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe2b1e9jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opsgenie" {...props}></Icon>
