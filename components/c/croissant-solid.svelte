<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ius514pkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ius514pkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:croissant-solid" {...props}></Icon>
