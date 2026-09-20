<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y56n58bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y56n58bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-v" {...props}></Icon>
