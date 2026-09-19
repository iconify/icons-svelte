<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6b6mob6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6b6mob6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:blood-drop-plus-filled" {...props}></Icon>
