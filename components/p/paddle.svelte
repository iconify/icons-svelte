<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/att-2cbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="att-2cbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:paddle" {...props}></Icon>
