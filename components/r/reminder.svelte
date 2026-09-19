<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5e10sboi.css';
import '../../css/n/n_757dk6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h5e10sboi"/><path class="n_757dk6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:reminder" {...props}></Icon>
