<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_k1ojhml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e_k1ojhml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-hebrew" {...props}></Icon>
