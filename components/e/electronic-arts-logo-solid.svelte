<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v22vrs4cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v22vrs4cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:electronic-arts-logo-solid" {...props}></Icon>
