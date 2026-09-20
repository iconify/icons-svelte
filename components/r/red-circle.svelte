<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2dutkr2l.css';
import '../../css/s/snpiwsb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="u2dutkr2l"/><circle class="snpiwsb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:red-circle" {...props}></Icon>
