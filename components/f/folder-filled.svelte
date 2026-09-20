<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhshkhtwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhshkhtwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-filled" {...props}></Icon>
