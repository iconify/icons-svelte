<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz3275pob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz3275pob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-cancel" {...props}></Icon>
