<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omojj5bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omojj5bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:common-lisp" {...props}></Icon>
