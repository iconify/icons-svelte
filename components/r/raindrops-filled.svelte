<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn31p9lwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gn31p9lwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:raindrops-filled" {...props}></Icon>
