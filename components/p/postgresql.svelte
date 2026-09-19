<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo1ccfb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vo1ccfb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:postgresql" {...props}></Icon>
