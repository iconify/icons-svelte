<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8am-97fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c8am-97fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pet-friendly-filled" {...props}></Icon>
