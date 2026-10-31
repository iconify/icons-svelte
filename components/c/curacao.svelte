<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7jllbb4j.css';
import '../../css/b/bx4_vlbad.css';
import '../../css/n/n3enlbj8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="l7jllbb4j"/><path class="bx4_vlbad"/><path class="n3enlbj8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:curacao" {...props}></Icon>
