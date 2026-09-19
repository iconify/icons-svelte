<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as0qs_ufy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as0qs_ufy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:c-plus-plus" {...props}></Icon>
