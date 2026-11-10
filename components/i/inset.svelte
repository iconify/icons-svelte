<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo9ibqbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uo9ibqbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:inset" {...props}></Icon>
