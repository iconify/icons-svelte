<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvjcoub6v.css';
import '../../css/e/efsylsb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gvjcoub6v"/><path class="efsylsb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chevron-up-outline" {...props}></Icon>
