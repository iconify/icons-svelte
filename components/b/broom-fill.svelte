<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xseahqb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xseahqb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:broom-fill" {...props}></Icon>
