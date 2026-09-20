<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp3zz-bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp3zz-bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:font-awesome" {...props}></Icon>
