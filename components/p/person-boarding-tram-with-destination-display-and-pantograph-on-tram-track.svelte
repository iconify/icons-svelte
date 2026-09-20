<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r48w19b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r48w19b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-boarding-tram-with-destination-display-and-pantograph-on-tram-track" {...props}></Icon>
