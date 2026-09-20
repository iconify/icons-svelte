<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wozf3nhyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wozf3nhyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:celebrate-fill" {...props}></Icon>
