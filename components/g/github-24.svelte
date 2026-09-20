<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd25lnj5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd25lnj5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:github-24" {...props}></Icon>
