<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cria1o_sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cria1o_sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:layers-check" {...props}></Icon>
