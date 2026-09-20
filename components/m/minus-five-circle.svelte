<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0t3ehl7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x0t3ehl7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:minus-five-circle" {...props}></Icon>
