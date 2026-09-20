<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/treqscctw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="treqscctw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:glasses-outline" {...props}></Icon>
