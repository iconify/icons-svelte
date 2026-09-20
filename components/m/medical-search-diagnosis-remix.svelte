<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lywbruj5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lywbruj5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:medical-search-diagnosis-remix" {...props}></Icon>
