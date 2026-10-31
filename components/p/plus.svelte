<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhzr79rbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhzr79rbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:plus" {...props}></Icon>
