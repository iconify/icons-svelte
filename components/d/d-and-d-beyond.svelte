<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azxiujbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="azxiujbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:d-and-d-beyond" {...props}></Icon>
