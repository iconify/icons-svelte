<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4ih4z8ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4ih4z8ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:iced" {...props}></Icon>
