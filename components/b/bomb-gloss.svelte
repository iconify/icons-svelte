<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng2aok_2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng2aok_2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bomb-gloss" {...props}></Icon>
