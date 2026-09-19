<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6l2v_wvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o6l2v_wvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:letterboxd" {...props}></Icon>
