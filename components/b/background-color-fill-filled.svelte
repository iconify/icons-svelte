<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jor-usn7v.css';
import '../../css/f/fj747pbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b jor-usn7v"/><rect class="b fj747pbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:background-color-fill-filled" {...props}></Icon>
