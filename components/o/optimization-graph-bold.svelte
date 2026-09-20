<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts8762bta.css';
import '../../css/a/au3jsqbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts8762bta"/><path class="au3jsqbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:optimization-graph-bold" {...props}></Icon>
