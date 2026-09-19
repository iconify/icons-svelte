<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1gwhibcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o1gwhibcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-left-6-circle-fill" {...props}></Icon>
