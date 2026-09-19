<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_28jmb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k_28jmb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:nut-hex" {...props}></Icon>
