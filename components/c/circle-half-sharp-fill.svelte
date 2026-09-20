<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es1__4bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="es1__4bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-half-sharp-fill" {...props}></Icon>
