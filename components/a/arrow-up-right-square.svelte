<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-7l-4pxq.css';
import '../../css/j/jor-usn7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-7l-4pxq"/><path class="jor-usn7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-right-square" {...props}></Icon>
