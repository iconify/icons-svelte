<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o72-pkb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o72-pkb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:puzzle-filled" {...props}></Icon>
