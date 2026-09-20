<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1ctc1phm.css';
import '../../css/y/ypchirliy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1ctc1phm"/><path class="ypchirliy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:fluid-light" {...props}></Icon>
