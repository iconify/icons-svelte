<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm-87qb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cm-87qb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:power-16-solid" {...props}></Icon>
