<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euw5a4tua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="euw5a4tua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:browser-error-404-remix" {...props}></Icon>
