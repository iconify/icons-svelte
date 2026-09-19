<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x68y6ab4a.css';
import '../../css/m/mgz8c9b8i.css';
import '../../css/u/u07nh0bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer x68y6ab4a"/><path class="duoicon-primary-layer mgz8c9b8i"/><path class="duoicon-secondary-layer u07nh0bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:battery" {...props}></Icon>
