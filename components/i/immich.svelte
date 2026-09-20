<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw7f53skv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw7f53skv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:immich" {...props}></Icon>
