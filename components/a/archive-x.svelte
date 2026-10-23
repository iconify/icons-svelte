<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxv2ymz5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxv2ymz5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:archive-x" {...props}></Icon>
