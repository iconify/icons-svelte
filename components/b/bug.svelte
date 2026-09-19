<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fma0zqbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fma0zqbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:bug" {...props}></Icon>
