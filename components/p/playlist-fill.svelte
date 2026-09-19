<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0_jmwy_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g0_jmwy_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:playlist-fill" {...props}></Icon>
