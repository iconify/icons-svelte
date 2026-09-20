<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb9onsblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb9onsblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:file-edit" {...props}></Icon>
