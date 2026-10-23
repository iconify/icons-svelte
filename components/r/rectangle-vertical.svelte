<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqbma1f2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqbma1f2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:rectangle-vertical" {...props}></Icon>
