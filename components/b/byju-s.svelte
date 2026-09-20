<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odx6vqbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odx6vqbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:byju-s" {...props}></Icon>
