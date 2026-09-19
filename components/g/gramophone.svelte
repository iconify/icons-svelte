<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p12_vcctc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="p12_vcctc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:gramophone" {...props}></Icon>
