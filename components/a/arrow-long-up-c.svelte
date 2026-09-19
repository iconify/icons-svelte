<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhxm6xbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhxm6xbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-long-up-c" {...props}></Icon>
