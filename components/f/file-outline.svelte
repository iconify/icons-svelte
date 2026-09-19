<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-msdc2cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-msdc2cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:file-outline" {...props}></Icon>
