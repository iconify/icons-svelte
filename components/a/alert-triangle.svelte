<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st2ftqbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="st2ftqbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alert-triangle" {...props}></Icon>
