<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eazp9w1_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eazp9w1_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:edit-pdf-remix" {...props}></Icon>
