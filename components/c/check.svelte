<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok-rcqbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":24};
const content = `<path class="ok-rcqbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:check" {...props}></Icon>
