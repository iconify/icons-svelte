<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbjc9sb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbjc9sb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pencil-ruler" {...props}></Icon>
