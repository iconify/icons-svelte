<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9th0b53y.css';
import '../../css/j/jik0uqbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d9th0b53y"/><path class="jik0uqbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-minus-bold" {...props}></Icon>
