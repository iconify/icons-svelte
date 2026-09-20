<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qycoj8bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qycoj8bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apachehadoop" {...props}></Icon>
