<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyr05pb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pyr05pb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:facebook-24" {...props}></Icon>
