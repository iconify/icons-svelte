<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezvng4b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ezvng4b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bus-solid" {...props}></Icon>
