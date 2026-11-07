<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtj37ub3j.css';
import '../../css/y/yvc3dk4hi.css';
import '../../css/g/g9srdqbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vtj37ub3j"/><path class="yvc3dk4hi"/><path class="g9srdqbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:car-battery-bold" {...props}></Icon>
