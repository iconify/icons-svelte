<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itw1ckbiw.css';
import '../../css/g/gryaribnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="itw1ckbiw"/><path class="gryaribnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloudy-night-outline" {...props}></Icon>
