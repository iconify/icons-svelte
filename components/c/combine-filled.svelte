<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af65gwbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af65gwbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:combine-filled" {...props}></Icon>
