<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9hw7ehsm.css';
import '../../css/g/g9h7rdbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9hw7ehsm"/><path class="g9h7rdbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:link" {...props}></Icon>
