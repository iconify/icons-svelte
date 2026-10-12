<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uawrme4my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24.9,"height":34.2};
const content = `<path class="uawrme4my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fivetran" {...props}></Icon>
