<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf7qo0fud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tf7qo0fud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:quote-message-solid" {...props}></Icon>
