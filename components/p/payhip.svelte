<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs9vhp30b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs9vhp30b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:payhip" {...props}></Icon>
