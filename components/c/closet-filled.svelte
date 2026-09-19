<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wguh654wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wguh654wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:closet-filled" {...props}></Icon>
