<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnz7wtb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mnz7wtb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:polaroid-solid" {...props}></Icon>
