<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maj0_wbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="maj0_wbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:residentevil" {...props}></Icon>
