<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agm8mccml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="agm8mccml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:open-stripe" {...props}></Icon>
