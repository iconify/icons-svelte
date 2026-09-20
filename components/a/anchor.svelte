<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sujk3jbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sujk3jbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:anchor" {...props}></Icon>
