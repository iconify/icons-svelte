<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk8an_ymz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hk8an_ymz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:revel-light" {...props}></Icon>
