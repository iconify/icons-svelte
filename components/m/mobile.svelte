<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul4ei0bva.css';
import '../../css/z/zqbyl-b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul4ei0bva"/><path class="zqbyl-b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mobile" {...props}></Icon>
