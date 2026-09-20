<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdzxziqai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kdzxziqai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:nginx-16" {...props}></Icon>
