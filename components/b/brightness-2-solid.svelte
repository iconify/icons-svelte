<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulz3mpfix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ulz3mpfix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:brightness-2-solid" {...props}></Icon>
