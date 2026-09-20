<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8infr9ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8infr9ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:dental-crown-1-bold" {...props}></Icon>
