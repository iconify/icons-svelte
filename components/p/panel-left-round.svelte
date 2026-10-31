<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idk7jvbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idk7jvbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-left-round" {...props}></Icon>
