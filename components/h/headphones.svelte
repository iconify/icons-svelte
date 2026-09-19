<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqx0q-9fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oqx0q-9fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:headphones" {...props}></Icon>
