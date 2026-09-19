<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzaj_mpyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hzaj_mpyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:barbell" {...props}></Icon>
