<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5fu5bc9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q5fu5bc9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:piggy-bank-solid" {...props}></Icon>
