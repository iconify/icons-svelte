<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqqx58b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqqx58b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-hat-2-fill" {...props}></Icon>
