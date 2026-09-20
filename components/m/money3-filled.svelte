<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flkqr0bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flkqr0bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money3-filled" {...props}></Icon>
