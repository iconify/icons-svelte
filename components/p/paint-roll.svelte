<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plhgtqbhj.css';
import '../../css/k/keeeh295c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plhgtqbhj"/><path class="keeeh295c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:paint-roll" {...props}></Icon>
