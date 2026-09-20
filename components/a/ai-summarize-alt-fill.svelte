<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw8y06qco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw8y06qco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-summarize-alt-fill" {...props}></Icon>
