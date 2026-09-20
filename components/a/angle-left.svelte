<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9nquyb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9nquyb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:angle-left" {...props}></Icon>
