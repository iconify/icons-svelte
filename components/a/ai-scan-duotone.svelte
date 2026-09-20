<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyze-dimw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyze-dimw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-scan-duotone" {...props}></Icon>
