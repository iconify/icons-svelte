<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs28-1_yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs28-1_yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:academia" {...props}></Icon>
