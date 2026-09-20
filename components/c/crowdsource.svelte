<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocf_5ubml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocf_5ubml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:crowdsource" {...props}></Icon>
