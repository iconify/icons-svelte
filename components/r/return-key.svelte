<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxqle7bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gxqle7bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:return-key" {...props}></Icon>
