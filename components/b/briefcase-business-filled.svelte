<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvc5zobxq.css';
import '../../css/c/curqijbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvc5zobxq"/><path clip-rule="evenodd" class="curqijbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:briefcase-business-filled" {...props}></Icon>
