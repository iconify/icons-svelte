<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq2j4ab8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq2j4ab8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:braintrust" {...props}></Icon>
