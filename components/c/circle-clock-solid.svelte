<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffjwj8xkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ffjwj8xkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:circle-clock-solid" {...props}></Icon>
