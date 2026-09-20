<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7l1v_d8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7l1v_d8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:contensis" {...props}></Icon>
