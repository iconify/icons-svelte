<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb0l61w-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nb0l61w-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-minus-sharp-fill" {...props}></Icon>
