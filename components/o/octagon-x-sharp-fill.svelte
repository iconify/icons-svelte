<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq5tbwb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pq5tbwb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:octagon-x-sharp-fill" {...props}></Icon>
