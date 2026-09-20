<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci7s_f6sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ci7s_f6sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:check-thick" {...props}></Icon>
