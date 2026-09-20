<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myqkzzb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="myqkzzb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:facebook-16" {...props}></Icon>
