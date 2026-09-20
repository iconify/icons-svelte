<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgytc7ilk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgytc7ilk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-down-left-box-sharp-fill" {...props}></Icon>
