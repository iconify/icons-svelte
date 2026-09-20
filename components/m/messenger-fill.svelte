<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc6x9foxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wc6x9foxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:messenger-fill" {...props}></Icon>
