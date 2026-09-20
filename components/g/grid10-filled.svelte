<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghum32j7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghum32j7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid10-filled" {...props}></Icon>
