<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8ltq07ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8ltq07ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:expand-less-circle-fill" {...props}></Icon>
