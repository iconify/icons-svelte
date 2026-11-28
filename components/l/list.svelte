<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb745pbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb745pbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:list" {...props}></Icon>
