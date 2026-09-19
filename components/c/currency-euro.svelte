<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iynpo30pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iynpo30pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:currency-euro" {...props}></Icon>
