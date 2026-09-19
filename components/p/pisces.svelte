<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_h__lbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h_h__lbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:pisces" {...props}></Icon>
