<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cec7lzbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cec7lzbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:folder-24" {...props}></Icon>
