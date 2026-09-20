<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5dpn6bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5dpn6bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cloud-data-transfer-remix" {...props}></Icon>
