<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e22ort1_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e22ort1_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:briefcase-alt" {...props}></Icon>
