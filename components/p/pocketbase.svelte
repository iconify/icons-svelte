<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uls39h0tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uls39h0tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pocketbase" {...props}></Icon>
