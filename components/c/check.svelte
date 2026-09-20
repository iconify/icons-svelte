<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjjr6sbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjjr6sbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:check" {...props}></Icon>
