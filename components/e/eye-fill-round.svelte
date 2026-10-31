<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nskupqbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nskupqbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:eye-fill-round" {...props}></Icon>
