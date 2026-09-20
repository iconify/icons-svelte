<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhgj0q6xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhgj0q6xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-down" {...props}></Icon>
