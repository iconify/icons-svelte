<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg-7l1u1i.css';
import '../../css/f/fua5fmpqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jg-7l1u1i"/><path class="fua5fmpqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-person-add" {...props}></Icon>
