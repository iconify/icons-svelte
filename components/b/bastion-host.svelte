<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra7tqub2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ra7tqub2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bastion-host" {...props}></Icon>
