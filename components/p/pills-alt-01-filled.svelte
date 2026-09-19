<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zywujyb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zywujyb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pills-alt-01-filled" {...props}></Icon>
