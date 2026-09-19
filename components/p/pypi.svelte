<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1aqaybva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b1aqaybva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:pypi" {...props}></Icon>
