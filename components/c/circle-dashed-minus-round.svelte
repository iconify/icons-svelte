<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cym504bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cym504bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-minus-round" {...props}></Icon>
