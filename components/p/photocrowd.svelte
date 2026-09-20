<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp-p7zbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp-p7zbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:photocrowd" {...props}></Icon>
