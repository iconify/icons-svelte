<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euqkqbwvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="euqkqbwvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:list" {...props}></Icon>
