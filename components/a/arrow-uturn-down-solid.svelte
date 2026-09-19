<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkscxqbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkscxqbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-down-solid" {...props}></Icon>
