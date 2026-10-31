<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvs3sen_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvs3sen_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bath-round" {...props}></Icon>
