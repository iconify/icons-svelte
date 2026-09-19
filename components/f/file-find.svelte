<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2nszzb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2nszzb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:file-find" {...props}></Icon>
