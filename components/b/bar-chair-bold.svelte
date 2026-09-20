<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7bi75b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d7bi75b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bar-chair-bold" {...props}></Icon>
