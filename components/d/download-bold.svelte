<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z671n4b7f.css';
import '../../css/o/o9b3pqbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z671n4b7f"/><path class="o9b3pqbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:download-bold" {...props}></Icon>
