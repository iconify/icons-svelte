<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukcc3lbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukcc3lbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:column-minus-fill-round" {...props}></Icon>
