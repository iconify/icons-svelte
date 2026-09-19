<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb9o4qvoo.css';
import '../../css/z/zfvyp8bow.css';
import '../../css/d/dw4cdfjco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb9o4qvoo"/><path class="zfvyp8bow"/><path class="dw4cdfjco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:repeat" {...props}></Icon>
