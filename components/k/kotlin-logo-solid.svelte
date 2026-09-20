<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryd5gqbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ryd5gqbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kotlin-logo-solid" {...props}></Icon>
