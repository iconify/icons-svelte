<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo6j7xbls.css';
import '../../css/v/vrpmrdbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lo6j7xbls"/><path class="vrpmrdbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-elo-engineering-insights" {...props}></Icon>
