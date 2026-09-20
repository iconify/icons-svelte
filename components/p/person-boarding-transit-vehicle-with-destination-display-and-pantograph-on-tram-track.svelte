<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvfqb6dsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qvfqb6dsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-boarding-transit-vehicle-with-destination-display-and-pantograph-on-tram-track" {...props}></Icon>
