<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyazd6i6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyazd6i6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-right-gloss" {...props}></Icon>
