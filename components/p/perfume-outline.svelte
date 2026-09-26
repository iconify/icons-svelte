<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq9-uch7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eq9-uch7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:perfume-outline" {...props}></Icon>
