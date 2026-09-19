<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsam74iwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsam74iwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:folder" {...props}></Icon>
