<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hab5lhbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hab5lhbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:brush4-filled" {...props}></Icon>
