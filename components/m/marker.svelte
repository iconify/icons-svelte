<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-ego69_b.css';
import '../../css/r/rz02wcb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer f-ego69_b"/><path class="duoicon-primary-layer rz02wcb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:marker" {...props}></Icon>
