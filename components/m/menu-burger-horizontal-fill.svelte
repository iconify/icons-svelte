<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufvu6tbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufvu6tbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-burger-horizontal-fill" {...props}></Icon>
