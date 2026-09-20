<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbdi6owtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbdi6owtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-alt-circle-right-solid" {...props}></Icon>
