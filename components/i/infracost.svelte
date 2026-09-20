<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghnfzw7so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghnfzw7so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:infracost" {...props}></Icon>
