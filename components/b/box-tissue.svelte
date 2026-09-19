<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd-g8ob1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gd-g8ob1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:box-tissue" {...props}></Icon>
