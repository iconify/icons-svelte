<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7spctb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k7spctb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:letter-m" {...props}></Icon>
