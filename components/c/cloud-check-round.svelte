<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojqjc3bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojqjc3bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-check-round" {...props}></Icon>
