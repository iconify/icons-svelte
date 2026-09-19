<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfz61u2be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfz61u2be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:contra-filled" {...props}></Icon>
