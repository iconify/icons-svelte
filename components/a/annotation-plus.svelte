<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6-ilxbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z6-ilxbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:annotation-plus" {...props}></Icon>
