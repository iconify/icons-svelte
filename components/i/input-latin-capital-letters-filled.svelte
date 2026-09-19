<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pepvs8ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pepvs8ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:input-latin-capital-letters-filled" {...props}></Icon>
